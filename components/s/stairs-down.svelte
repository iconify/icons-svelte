<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3j6f0b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3j6f0b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stairs-down" {...props}></Icon>
