<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phfr-hjhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="phfr-hjhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:t" {...props}></Icon>
