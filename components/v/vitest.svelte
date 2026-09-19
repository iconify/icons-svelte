<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3f6ugbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o3f6ugbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vitest" {...props}></Icon>
