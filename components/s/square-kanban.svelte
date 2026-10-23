<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbd7dvebg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbd7dvebg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-kanban" {...props}></Icon>
