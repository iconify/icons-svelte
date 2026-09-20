<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3au2j9yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3au2j9yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:starling-bank" {...props}></Icon>
