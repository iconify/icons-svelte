<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg533cbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg533cbes primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wave-square-duotone" {...props}></Icon>
