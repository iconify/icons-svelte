<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzbfeebpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzbfeebpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:threeraysabove" {...props}></Icon>
