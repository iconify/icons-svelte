<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pryzvqbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pryzvqbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:techcrunch-dark" {...props}></Icon>
