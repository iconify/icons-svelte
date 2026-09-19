<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_6e4bfxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_6e4bfxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shield" {...props}></Icon>
