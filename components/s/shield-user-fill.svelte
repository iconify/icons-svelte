<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd4x32brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nd4x32brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-user-fill" {...props}></Icon>
