<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjg_cfqen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjg_cfqen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tree-fill-round" {...props}></Icon>
