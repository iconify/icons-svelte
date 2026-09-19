<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo0w98b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="uo0w98b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:spinner-refresh" {...props}></Icon>
