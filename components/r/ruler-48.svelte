<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fggx0lbvr.css';
import '../../css/q/q01m64b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fggx0lbvr"/><path class="q01m64b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ruler-48" {...props}></Icon>
