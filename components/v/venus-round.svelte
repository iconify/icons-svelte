<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q09b9zepi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q09b9zepi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:venus-round" {...props}></Icon>
