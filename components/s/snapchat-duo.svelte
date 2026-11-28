<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs2lp--bm.css';
import '../../css/r/rn8fz8f3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zs2lp--bm"/><path class="primary rn8fz8f3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:snapchat-duo" {...props}></Icon>
