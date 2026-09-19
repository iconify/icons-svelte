<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8za_lbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="n8za_lbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:sina-weibo" {...props}></Icon>
