<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rci8lkegk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rci8lkegk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:skysports-news" {...props}></Icon>
