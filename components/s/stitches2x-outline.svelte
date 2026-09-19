<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk7lobb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pk7lobb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:stitches2x-outline" {...props}></Icon>
