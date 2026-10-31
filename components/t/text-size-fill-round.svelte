<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz-3uhbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz-3uhbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-size-fill-round" {...props}></Icon>
