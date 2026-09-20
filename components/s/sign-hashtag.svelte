<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbss98bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbss98bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sign-hashtag" {...props}></Icon>
