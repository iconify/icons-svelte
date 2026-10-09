<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acvp9rbcm.css';
import '../../css/e/ev1t4gbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="acvp9rbcm"/><path class="ev1t4gbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-bottle-48" {...props}></Icon>
