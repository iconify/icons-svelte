<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrp22s0pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrp22s0pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sliders-h" {...props}></Icon>
