<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-h-_ubmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g-h-_ubmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:wifi-abnormal-filled" {...props}></Icon>
