<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs4nm6bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs4nm6bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-help-fill-round" {...props}></Icon>
