<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awp9mj42a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="awp9mj42a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:trash" {...props}></Icon>
