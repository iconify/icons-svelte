<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k46w-zb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k46w-zb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:serverless" {...props}></Icon>
