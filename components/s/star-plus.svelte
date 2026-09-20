<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq-xevz_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq-xevz_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:star-plus" {...props}></Icon>
