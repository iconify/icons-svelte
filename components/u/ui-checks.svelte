<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogpk27bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ogpk27bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ui-checks" {...props}></Icon>
