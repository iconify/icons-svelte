<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aar2s783j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aar2s783j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sure-finance-light" {...props}></Icon>
