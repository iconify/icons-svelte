<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb3sy8b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb3sy8b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:trademark-circle" {...props}></Icon>
