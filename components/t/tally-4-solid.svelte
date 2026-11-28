<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekgl8qbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekgl8qbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-4-solid" {...props}></Icon>
