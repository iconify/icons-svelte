<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvm2ckb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gvm2ckb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrutiny-light" {...props}></Icon>
