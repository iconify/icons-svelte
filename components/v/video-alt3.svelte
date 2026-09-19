<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6tzhbbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k6tzhbbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:video-alt3" {...props}></Icon>
