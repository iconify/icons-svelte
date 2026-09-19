<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9bal6b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w9bal6b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:theme" {...props}></Icon>
