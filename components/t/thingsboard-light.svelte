<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu07umcxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zu07umcxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thingsboard-light" {...props}></Icon>
