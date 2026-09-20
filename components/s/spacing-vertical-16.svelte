<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh6v09b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xh6v09b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:spacing-vertical-16" {...props}></Icon>
