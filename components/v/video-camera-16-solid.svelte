<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aomy0cbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aomy0cbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:video-camera-16-solid" {...props}></Icon>
