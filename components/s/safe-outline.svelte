<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n59582bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n59582bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:safe-outline" {...props}></Icon>
