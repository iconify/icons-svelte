<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke35x6olc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke35x6olc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-secure-outline" {...props}></Icon>
