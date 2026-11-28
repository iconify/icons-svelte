<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4mgdvbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4mgdvbnm primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-split-vertical-duotone" {...props}></Icon>
