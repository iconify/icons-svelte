<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc--c-byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc--c-byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:soda-can" {...props}></Icon>
