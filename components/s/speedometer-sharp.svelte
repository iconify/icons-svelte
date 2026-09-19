<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9p5mvjco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9p5mvjco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:speedometer-sharp" {...props}></Icon>
