<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1k0_9_to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g1k0_9_to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:smiley-face" {...props}></Icon>
