<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0q4cdc_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0q4cdc_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:smile-heart" {...props}></Icon>
