<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz7crbc0o.css';
import '../../css/l/lp4l0xmec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nz7crbc0o"/><path class="lp4l0xmec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-search-48" {...props}></Icon>
