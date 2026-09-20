<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr6r9tbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr6r9tbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unlocked-check" {...props}></Icon>
