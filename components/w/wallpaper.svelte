<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8_gg4bxv.css';
import '../../css/w/wa7uyac8k.css';
import '../../css/t/t7gs68bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8_gg4bxv"/><path class="wa7uyac8k"/><path class="t7gs68bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wallpaper" {...props}></Icon>
