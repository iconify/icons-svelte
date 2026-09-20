<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_ieiz18n.css';
import '../../css/d/d5xclqbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_ieiz18n"/><path class="d5xclqbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:syncloud" {...props}></Icon>
