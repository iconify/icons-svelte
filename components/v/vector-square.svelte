<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utg5x7c1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utg5x7c1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:vector-square" {...props}></Icon>
