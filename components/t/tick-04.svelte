<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9q138bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9q138bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tick-04" {...props}></Icon>
