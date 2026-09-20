<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwo41-b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwo41-b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:twitter-logo-1" {...props}></Icon>
