<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgqpeab4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgqpeab4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:service-toolbox" {...props}></Icon>
