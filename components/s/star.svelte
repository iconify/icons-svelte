<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnzw39bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pnzw39bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:star" {...props}></Icon>
