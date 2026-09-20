<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0bta1xpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0bta1xpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-circle-outline" {...props}></Icon>
