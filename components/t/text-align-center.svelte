<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsvefgb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsvefgb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-align-center" {...props}></Icon>
