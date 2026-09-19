<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt_dd0byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tt_dd0byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vulkan" {...props}></Icon>
