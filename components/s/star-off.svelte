<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl2na2b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl2na2b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:star-off" {...props}></Icon>
