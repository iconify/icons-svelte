<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzdv_vtcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bzdv_vtcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:video-camera-arrow-up-right-16-solid" {...props}></Icon>
