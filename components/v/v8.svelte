<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpf3z12ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wpf3z12ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:v8" {...props}></Icon>
