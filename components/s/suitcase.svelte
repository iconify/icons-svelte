<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd-uo8olg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-uo8olg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:suitcase" {...props}></Icon>
