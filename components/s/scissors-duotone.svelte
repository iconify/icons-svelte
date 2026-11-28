<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggmuwmnbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggmuwmnbo primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scissors-duotone" {...props}></Icon>
