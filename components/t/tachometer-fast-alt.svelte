<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh3y5mqlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh3y5mqlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:tachometer-fast-alt" {...props}></Icon>
