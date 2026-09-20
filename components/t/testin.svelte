<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sabln9pcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sabln9pcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:testin" {...props}></Icon>
