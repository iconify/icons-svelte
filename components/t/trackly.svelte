<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr7toqbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fr7toqbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trackly" {...props}></Icon>
