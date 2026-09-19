<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9azg15-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d9azg15-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:wolfram" {...props}></Icon>
