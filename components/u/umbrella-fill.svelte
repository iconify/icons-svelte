<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgkihrgoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgkihrgoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:umbrella-fill" {...props}></Icon>
