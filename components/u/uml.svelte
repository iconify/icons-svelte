<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfpo1o8mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfpo1o8mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:uml" {...props}></Icon>
