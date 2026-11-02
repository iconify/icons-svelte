<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-_x7zkuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-_x7zkuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wechat-fill" {...props}></Icon>
