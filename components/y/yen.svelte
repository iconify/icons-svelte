<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7lm1fbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="i7lm1fbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:yen" {...props}></Icon>
