<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0y6rabqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0y6rabqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:tally-3" {...props}></Icon>
