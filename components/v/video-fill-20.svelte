<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6qk_lquz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c6qk_lquz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-fill-20" {...props}></Icon>
