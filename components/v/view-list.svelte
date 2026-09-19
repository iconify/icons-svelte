<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5q44-hod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y5q44-hod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:view-list" {...props}></Icon>
