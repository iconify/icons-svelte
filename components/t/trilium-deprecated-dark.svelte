<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abgwjst6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abgwjst6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trilium-deprecated-dark" {...props}></Icon>
