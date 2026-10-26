<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w294ishiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w294ishiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:stars" {...props}></Icon>
