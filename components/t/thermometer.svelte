<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ladf9qkxg.css';
import '../../css/x/x28r8k_ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ladf9qkxg"/><path class="x28r8k_ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:thermometer" {...props}></Icon>
