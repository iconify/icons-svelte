<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj-wp8-cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-wp8-cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shrimp-off" {...props}></Icon>
