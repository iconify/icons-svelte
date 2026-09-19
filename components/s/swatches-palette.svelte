<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye42pybga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye42pybga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:swatches-palette" {...props}></Icon>
