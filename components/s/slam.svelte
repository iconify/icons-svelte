<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxq4srb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxq4srb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:slam" {...props}></Icon>
