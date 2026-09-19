<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6lwejbts.css';
import '../../css/b/b12gxvr_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6lwejbts"/><circle class="b12gxvr_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:yin-yang" {...props}></Icon>
