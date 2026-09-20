<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziaf69b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ziaf69b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:suitcase-and-locked-lock-with-keyhole" {...props}></Icon>
