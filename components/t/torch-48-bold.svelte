<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bze383b6h.css';
import '../../css/p/ppuwdj0xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bze383b6h"/><path class="ppuwdj0xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:torch-48-bold" {...props}></Icon>
