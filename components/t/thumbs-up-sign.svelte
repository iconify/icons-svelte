<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piax8-b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="piax8-b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:thumbs-up-sign" {...props}></Icon>
