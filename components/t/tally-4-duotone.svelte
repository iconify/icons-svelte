<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zahzeybal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zahzeybal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-4-duotone" {...props}></Icon>
