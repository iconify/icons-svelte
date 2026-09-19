<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuf4_ybad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuf4_ybad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:stack-overflow" {...props}></Icon>
