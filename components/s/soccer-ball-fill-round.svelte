<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk6n9fbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk6n9fbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:soccer-ball-fill-round" {...props}></Icon>
