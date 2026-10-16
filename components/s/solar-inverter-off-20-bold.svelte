<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azwzitbqs.css';
import '../../css/h/h4q4ylb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="azwzitbqs"/><path class="h4q4ylb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-off-20-bold" {...props}></Icon>
