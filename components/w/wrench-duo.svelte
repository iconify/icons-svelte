<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_xmpxb6b.css';
import '../../css/n/nkm2n0b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_xmpxb6b secondary"/><path class="nkm2n0b6m primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wrench-duo" {...props}></Icon>
