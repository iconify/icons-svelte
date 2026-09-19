<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3vv2btbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3vv2btbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:swap-fill" {...props}></Icon>
