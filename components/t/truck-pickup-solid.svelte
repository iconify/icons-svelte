<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paa52gbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="paa52gbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:truck-pickup-solid" {...props}></Icon>
