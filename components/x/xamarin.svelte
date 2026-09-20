<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjylu9y7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rjylu9y7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xamarin" {...props}></Icon>
