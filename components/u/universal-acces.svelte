<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocmpgtb3x.css';
import '../../css/j/j0rk_8u7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocmpgtb3x"/><path class="j0rk_8u7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:universal-acces" {...props}></Icon>
