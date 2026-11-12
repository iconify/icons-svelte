<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqtotg3-l.css';
import '../../css/p/p9wzaub_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vqtotg3-l"/><path class="p9wzaub_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:t3-code" {...props}></Icon>
