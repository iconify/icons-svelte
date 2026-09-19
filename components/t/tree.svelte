<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t99n1acxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t99n1acxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tree" {...props}></Icon>
