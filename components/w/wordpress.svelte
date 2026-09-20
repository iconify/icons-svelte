<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh70i435x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mh70i435x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wordpress" {...props}></Icon>
