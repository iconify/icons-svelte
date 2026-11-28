<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkovyh8fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkovyh8fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:stop-circle" {...props}></Icon>
