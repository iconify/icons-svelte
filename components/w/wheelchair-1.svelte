<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9cq85lbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9cq85lbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:wheelchair-1" {...props}></Icon>
