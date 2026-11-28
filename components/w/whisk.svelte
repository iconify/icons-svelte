<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nme2-ceqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nme2-ceqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:whisk" {...props}></Icon>
