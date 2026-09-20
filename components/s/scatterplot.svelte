<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwb7h4upf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwb7h4upf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:scatterplot" {...props}></Icon>
