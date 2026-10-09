<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvh-2kb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vvh-2kb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-dashed-48" {...props}></Icon>
