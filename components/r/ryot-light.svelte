<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pufzx1blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440.71,"height":440.63,"left":36.13,"top":36.34};
const content = `<path class="pufzx1blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ryot-light" {...props}></Icon>
