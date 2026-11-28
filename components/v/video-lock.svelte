<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euwbrpbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euwbrpbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:video-lock" {...props}></Icon>
