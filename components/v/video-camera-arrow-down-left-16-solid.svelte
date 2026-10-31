<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4h4q_bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d4h4q_bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:video-camera-arrow-down-left-16-solid" {...props}></Icon>
