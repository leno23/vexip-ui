<template>
  <Space>
    <Tooltip trigger="hover" placement="top">
      <Button>
        悬停触发
      </Button>
      <template #tip>
        一些提示的内容
      </template>
    </Tooltip>
    <Tooltip trigger="click" placement="right">
      <Button>
        点击触发
      </Button>
      <template #tip>
        一些提示的内容
      </template>
    </Tooltip>
  </Space>
</template>
