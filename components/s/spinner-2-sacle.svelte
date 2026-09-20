<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h43-4kifw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h43-4kifw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spinner-2-sacle" {...props}></Icon>
