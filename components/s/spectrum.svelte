<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mset3p40f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mset3p40f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spectrum" {...props}></Icon>
