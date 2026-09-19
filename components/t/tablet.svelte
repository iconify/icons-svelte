<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xad1hdcaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xad1hdcaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:tablet" {...props}></Icon>
