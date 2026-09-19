<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glq10si6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="glq10si6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:torso-business" {...props}></Icon>
