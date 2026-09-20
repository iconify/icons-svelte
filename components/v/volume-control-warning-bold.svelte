<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u98efjc-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u98efjc-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:volume-control-warning-bold" {...props}></Icon>
