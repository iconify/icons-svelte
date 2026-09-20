<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tij7y1zzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tij7y1zzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-key" {...props}></Icon>
