<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiz190byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qiz190byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-dashed" {...props}></Icon>
