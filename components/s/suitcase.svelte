<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqtuv14sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="nqtuv14sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:suitcase" {...props}></Icon>
