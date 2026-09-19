<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qao93n-ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qao93n-ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tree-deciduous" {...props}></Icon>
