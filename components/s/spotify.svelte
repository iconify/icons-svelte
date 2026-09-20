<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnjay0bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnjay0bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spotify" {...props}></Icon>
