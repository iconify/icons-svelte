<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1pi9x57x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="n1pi9x57x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:volume-disabled" {...props}></Icon>
