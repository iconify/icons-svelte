<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_ufj2b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ufj2b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:swipe-down-gesture" {...props}></Icon>
