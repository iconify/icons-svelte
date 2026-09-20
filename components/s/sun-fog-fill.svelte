<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi0i5it0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi0i5it0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sun-fog-fill" {...props}></Icon>
