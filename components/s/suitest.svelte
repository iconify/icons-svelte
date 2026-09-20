<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl7l21bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl7l21bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:suitest" {...props}></Icon>
