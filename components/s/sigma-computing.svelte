<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es1ac2bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":32};
const content = `<path class="es1ac2bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sigma-computing" {...props}></Icon>
