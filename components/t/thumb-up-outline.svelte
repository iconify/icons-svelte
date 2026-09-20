<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwqeewr-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dwqeewr-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:thumb-up-outline" {...props}></Icon>
