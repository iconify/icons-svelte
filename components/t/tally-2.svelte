<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4k6q8q-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4k6q8q-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tally-2" {...props}></Icon>
