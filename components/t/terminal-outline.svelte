<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njic2363g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="njic2363g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:terminal-outline" {...props}></Icon>
