<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pde9zma4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pde9zma4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:stack-exchange" {...props}></Icon>
