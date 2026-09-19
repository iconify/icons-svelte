<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w14ao9mev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w14ao9mev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:stairs-up-arrow" {...props}></Icon>
