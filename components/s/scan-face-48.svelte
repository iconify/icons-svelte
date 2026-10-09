<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sadb4lb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sadb4lb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-face-48" {...props}></Icon>
