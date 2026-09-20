<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuycb9bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuycb9bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wifi-2" {...props}></Icon>
