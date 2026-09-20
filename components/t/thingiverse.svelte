<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1qdg1bld.css';
import '../../css/s/s519vbn7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k1qdg1bld"/><path class="s519vbn7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thingiverse" {...props}></Icon>
