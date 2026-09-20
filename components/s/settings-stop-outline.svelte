<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6_f94bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6_f94bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:settings-stop-outline" {...props}></Icon>
