<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijzwfucfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijzwfucfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:satellite-solid" {...props}></Icon>
