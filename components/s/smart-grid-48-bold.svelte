<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6nfsjb9y.css';
import '../../css/q/qotc-vbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r6nfsjb9y"/><path class="qotc-vbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-grid-48-bold" {...props}></Icon>
