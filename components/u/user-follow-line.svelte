<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4uuzxt7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4uuzxt7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-follow-line" {...props}></Icon>
