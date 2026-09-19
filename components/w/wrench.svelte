<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfue8cbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfue8cbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:wrench" {...props}></Icon>
