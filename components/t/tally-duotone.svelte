<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mratxfbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mratxfbzu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-duotone" {...props}></Icon>
