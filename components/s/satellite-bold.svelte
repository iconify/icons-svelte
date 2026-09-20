<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0-i_vl6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0-i_vl6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:satellite-bold" {...props}></Icon>
