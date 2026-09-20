<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndgwe3cri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ndgwe3cri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zublo-light" {...props}></Icon>
