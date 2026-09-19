<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-8jss4sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e-8jss4sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:tank" {...props}></Icon>
