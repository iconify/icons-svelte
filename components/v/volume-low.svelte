<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh956kziz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh956kziz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:volume-low" {...props}></Icon>
