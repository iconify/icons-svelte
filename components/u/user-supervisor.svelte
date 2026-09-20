<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jycmdkbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jycmdkbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-supervisor" {...props}></Icon>
