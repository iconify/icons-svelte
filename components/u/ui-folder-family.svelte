<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3j1uwd6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d3j1uwd6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ui-folder-family" {...props}></Icon>
