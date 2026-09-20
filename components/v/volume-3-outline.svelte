<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncetcdbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ncetcdbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:volume-3-outline" {...props}></Icon>
