<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzwtx_bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzwtx_bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wenxin" {...props}></Icon>
