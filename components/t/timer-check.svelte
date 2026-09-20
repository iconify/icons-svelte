<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9y_8b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv9y_8b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-check" {...props}></Icon>
