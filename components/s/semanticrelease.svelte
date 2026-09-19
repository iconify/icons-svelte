<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z973zsazu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":444,"height":512};
const content = `<path class="z973zsazu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:semanticrelease" {...props}></Icon>
