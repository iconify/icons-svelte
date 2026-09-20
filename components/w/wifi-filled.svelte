<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks-rnpbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ks-rnpbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:wifi-filled" {...props}></Icon>
