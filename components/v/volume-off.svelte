<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyjii7bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyjii7bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:volume-off" {...props}></Icon>
