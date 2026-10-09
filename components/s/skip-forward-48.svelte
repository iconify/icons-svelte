<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy4sow8xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uy4sow8xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skip-forward-48" {...props}></Icon>
