<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksjm_nbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksjm_nbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slideshow-fill" {...props}></Icon>
