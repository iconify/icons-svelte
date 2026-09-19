<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g18q7hdew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1024};
const content = `<path class="g18q7hdew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:spoon" {...props}></Icon>
