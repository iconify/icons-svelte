<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdo9_1h6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdo9_1h6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-flash-fill" {...props}></Icon>
