<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sou8e1b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sou8e1b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:suitcase-x" {...props}></Icon>
