<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkrje0bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wkrje0bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tabletennis" {...props}></Icon>
