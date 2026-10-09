<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aawa8wi0p.css';
import '../../css/p/pv-ojy8ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aawa8wi0p"/><path class="pv-ojy8ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signature-48" {...props}></Icon>
