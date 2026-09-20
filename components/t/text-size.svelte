<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2w4mlbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2w4mlbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:text-size" {...props}></Icon>
