<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ird1tc7rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ird1tc7rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:watering-can-check" {...props}></Icon>
