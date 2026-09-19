<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nukmbjz2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nukmbjz2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ui-menu-grid2x-outline" {...props}></Icon>
