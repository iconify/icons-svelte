<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obz2q_blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obz2q_blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:utensils-check" {...props}></Icon>
