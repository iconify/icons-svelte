<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3cyy04nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3cyy04nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:split-horizontal" {...props}></Icon>
