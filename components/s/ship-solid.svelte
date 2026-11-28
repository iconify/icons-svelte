<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxtfrqb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxtfrqb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ship-solid" {...props}></Icon>
