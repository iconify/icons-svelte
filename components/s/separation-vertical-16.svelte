<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnfu2ibyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vnfu2ibyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:separation-vertical-16" {...props}></Icon>
