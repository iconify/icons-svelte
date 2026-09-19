<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwh8l9bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwh8l9bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ruler-add" {...props}></Icon>
