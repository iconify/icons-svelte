<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv-zjb-dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv-zjb-dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:softpedia" {...props}></Icon>
