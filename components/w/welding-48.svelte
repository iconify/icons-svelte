<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayli8kbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ayli8kbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:welding-48" {...props}></Icon>
