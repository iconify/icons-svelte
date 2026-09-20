<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abwve-4qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abwve-4qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trilium-deprecated-light" {...props}></Icon>
