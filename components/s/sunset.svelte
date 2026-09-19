<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc8jj7o6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oc8jj7o6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sunset" {...props}></Icon>
