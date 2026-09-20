<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muiaksnph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="muiaksnph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snowshare-dark" {...props}></Icon>
