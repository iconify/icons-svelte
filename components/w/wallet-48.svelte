<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7-dvibjv.css';
import '../../css/c/c2_o5pxqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o7-dvibjv"/><path class="c2_o5pxqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wallet-48" {...props}></Icon>
