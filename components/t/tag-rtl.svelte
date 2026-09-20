<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn3k_kbtr.css';
import '../../css/s/s13wyyboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bn3k_kbtr"/><circle class="s13wyyboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:tag-rtl" {...props}></Icon>
