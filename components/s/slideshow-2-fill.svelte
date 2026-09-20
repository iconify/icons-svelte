<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj5ckp7co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj5ckp7co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slideshow-2-fill" {...props}></Icon>
