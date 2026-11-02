<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jze89zb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jze89zb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:typography-fill" {...props}></Icon>
