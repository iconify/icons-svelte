<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br_hr0bcl.css';
import '../../css/g/gka_evgvf.css';
import '../../css/g/gw1hyez2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="br_hr0bcl"/><path class="gka_evgvf"/><path class="gw1hyez2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tree-48-bold" {...props}></Icon>
