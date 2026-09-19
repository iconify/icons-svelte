<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxvvz6jiy.css';
import '../../css/c/c_v1vmbxo.css';
import '../../css/k/kev1szbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kxvvz6jiy"/><path class="c_v1vmbxo"/><path class="kev1szbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:rss" {...props}></Icon>
