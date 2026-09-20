<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6z9ar0tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o6z9ar0tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:travelperk-light" {...props}></Icon>
