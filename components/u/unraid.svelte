<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu0u3lhjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yu0u3lhjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:unraid" {...props}></Icon>
