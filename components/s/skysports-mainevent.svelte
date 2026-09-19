<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbu0xac7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbu0xac7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:skysports-mainevent" {...props}></Icon>
