<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrvcwlpbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrvcwlpbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-trending-down-sharp-fill" {...props}></Icon>
