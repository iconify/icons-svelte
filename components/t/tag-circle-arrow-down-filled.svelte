<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxjbxrbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nxjbxrbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-circle-arrow-down-filled" {...props}></Icon>
