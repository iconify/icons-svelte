<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un47udnvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="un47udnvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shields-io-light" {...props}></Icon>
