<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j48_gdb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j48_gdb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:security-scan-filled" {...props}></Icon>
