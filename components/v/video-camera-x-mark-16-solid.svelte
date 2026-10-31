<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0q5zdfdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t0q5zdfdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:video-camera-x-mark-16-solid" {...props}></Icon>
