<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4-pn4mrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4-pn4mrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:row-minus-fill-round" {...props}></Icon>
