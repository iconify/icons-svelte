<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvq-2xblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wvq-2xblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:storage" {...props}></Icon>
