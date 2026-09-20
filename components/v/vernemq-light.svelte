<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anj8b-evo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anj8b-evo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vernemq-light" {...props}></Icon>
