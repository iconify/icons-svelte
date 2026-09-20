<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv5vvub5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv5vvub5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:yamaha-corporation" {...props}></Icon>
