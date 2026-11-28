<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv8pwxbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv8pwxbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user" {...props}></Icon>
