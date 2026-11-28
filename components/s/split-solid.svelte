<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3peuop-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3peuop-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:split-solid" {...props}></Icon>
