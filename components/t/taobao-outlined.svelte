<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_2qah0lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r_2qah0lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:taobao-outlined" {...props}></Icon>
