<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgsozi8rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2208,"height":1440};
const content = `<path class="rgsozi8rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:yahoo-japan" {...props}></Icon>
