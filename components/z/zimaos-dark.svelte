<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xicidgszj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xicidgszj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zimaos-dark" {...props}></Icon>
