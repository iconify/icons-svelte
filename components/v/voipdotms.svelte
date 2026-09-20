<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqn9yz3js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqn9yz3js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:voipdotms" {...props}></Icon>
