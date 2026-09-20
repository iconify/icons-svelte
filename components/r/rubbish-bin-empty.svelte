<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-lyb0boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-lyb0boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rubbish-bin-empty" {...props}></Icon>
