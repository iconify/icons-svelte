<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaoax90by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaoax90by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:subway-fill" {...props}></Icon>
