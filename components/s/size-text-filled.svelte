<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp4d9t4hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xp4d9t4hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:size-text-filled" {...props}></Icon>
