
ccflags-$(CONFIG_PM_DEBUG)	:= -DDEBUG

obj-y				+= qos.o
obj-$(CONFIG_PM)		+= main.o
obj-$(CONFIG_VT_CONSOLE_SLEEP)	+= console.o
obj-$(CONFIG_FREEZER)		+= process.o
obj-$(CONFIG_SUSPEND)		+= suspend.o
obj-$(CONFIG_PM_TEST_SUSPEND)	+= suspend_test.o
obj-$(CONFIG_HIBERNATION)	+= hibernate.o snapshot.o swap.o user.o \
				   block_io.o crc_check.o
obj-$(CONFIG_PM_AUTOSLEEP)	+= autosleep.o
obj-$(CONFIG_PM_WAKELOCKS)	+= wakelock.o
obj-$(CONFIG_SUSPEND_TIME)	+= suspend_time.o

obj-$(CONFIG_MAGIC_SYSRQ)	+= poweroff.o

obj-$(CONFIG_SUSPEND)	+= wakeup_reason.o

ccflags-$(CONFIG_HISI_SNAPSHOT_BOOT) += -DUSE_FIXED_SMALL_CHUNK
obj-$(CONFIG_HISI_SNAPSHOT_BOOT) += compress.o compress_wrapper.o
