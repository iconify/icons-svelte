<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn0zm5bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn0zm5bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:world-o" {...props}></Icon>
