<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1fybybou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="n1fybybou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:triangle-right" {...props}></Icon>
