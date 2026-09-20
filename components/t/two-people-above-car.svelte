<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7port6eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d7port6eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-people-above-car" {...props}></Icon>
