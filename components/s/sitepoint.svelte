<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed67yt6ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed67yt6ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sitepoint" {...props}></Icon>
