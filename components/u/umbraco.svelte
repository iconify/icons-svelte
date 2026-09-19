<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez5cvnbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":510,"height":512};
const content = `<path class="ez5cvnbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:umbraco" {...props}></Icon>
