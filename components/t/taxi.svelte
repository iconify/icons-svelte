<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igjfo-bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="igjfo-bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:taxi" {...props}></Icon>
