<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/porygp4eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="porygp4eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ui-menu-grid" {...props}></Icon>
