<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww4fyqbuj.css';
import '../../css/h/hu3x240rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ww4fyqbuj"/><path class="hu3x240rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning" {...props}></Icon>
