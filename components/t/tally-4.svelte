<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi6gjmbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6gjmbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tally-4" {...props}></Icon>
