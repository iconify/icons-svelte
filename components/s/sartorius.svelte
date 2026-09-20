<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r78ikkbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r78ikkbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sartorius" {...props}></Icon>
