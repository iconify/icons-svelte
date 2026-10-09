<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxx9g-boz.css';
import '../../css/e/elto8jbuv.css';
import '../../css/d/dysie4bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uxx9g-boz"/><path class="elto8jbuv"/><path class="dysie4bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vector-pen-20" {...props}></Icon>
