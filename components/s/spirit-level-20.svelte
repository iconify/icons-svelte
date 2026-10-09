<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_lk_zxsl.css';
import '../../css/x/xjb0j7b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i_lk_zxsl"/><path class="xjb0j7b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spirit-level-20" {...props}></Icon>
