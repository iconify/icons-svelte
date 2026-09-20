<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk9qaabaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk9qaabaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tele-5" {...props}></Icon>
