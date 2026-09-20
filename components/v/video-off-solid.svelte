<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2sapj_7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g2sapj_7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:video-off-solid" {...props}></Icon>
