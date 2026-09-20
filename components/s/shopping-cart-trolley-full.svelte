<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjnoqlmbw.css';
import '../../css/m/mw0oakbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjnoqlmbw"/><path class="mw0oakbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:shopping-cart-trolley-full" {...props}></Icon>
