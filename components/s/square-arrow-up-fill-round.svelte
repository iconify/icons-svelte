<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz79s0rdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz79s0rdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-up-fill-round" {...props}></Icon>
