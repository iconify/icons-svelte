<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1mdf92vw.css';
import '../../css/d/dvo8x3sla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m1mdf92vw"/><path class="dvo8x3sla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scanner-48" {...props}></Icon>
