<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfql7dklk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vfql7dklk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:smile-filled" {...props}></Icon>
