<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g307o3kzp.css';
import '../../css/u/ubccq2blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g307o3kzp"/><path class="ubccq2blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sofe" {...props}></Icon>
