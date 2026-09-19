<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4w5c7bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y4w5c7bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:x-filled" {...props}></Icon>
