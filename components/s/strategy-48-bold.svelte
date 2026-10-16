<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4lx5fghu.css';
import '../../css/d/d3p8osbna.css';
import '../../css/d/dxicmz50x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i4lx5fghu"/><path class="d3p8osbna"/><path class="dxicmz50x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:strategy-48-bold" {...props}></Icon>
