<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eppc3o07n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eppc3o07n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-partly-lightning" {...props}></Icon>
