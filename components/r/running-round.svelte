<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjdle_l-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjdle_l-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:running-round" {...props}></Icon>
