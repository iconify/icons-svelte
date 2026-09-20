<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmyu2ouwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmyu2ouwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:xing-logo" {...props}></Icon>
