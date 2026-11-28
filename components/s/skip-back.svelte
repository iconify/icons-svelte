<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wflgxsbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wflgxsbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:skip-back" {...props}></Icon>
