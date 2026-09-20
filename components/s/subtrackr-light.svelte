<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl0xf91ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pl0xf91ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:subtrackr-light" {...props}></Icon>
