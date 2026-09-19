<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yknjv8bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yknjv8bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:size-text" {...props}></Icon>
