<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmcricc-j.css';
import '../../css/k/kkd7-e-we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pmcricc-j"/><path class="kkd7-e-we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-plug-48-bold" {...props}></Icon>
