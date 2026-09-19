<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg9et_bct.css';
import '../../css/j/j9xiqe_ui.css';
import '../../css/z/zyroygmzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rg9et_bct"/><path class="j9xiqe_ui"/><path class="zyroygmzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:tongue" {...props}></Icon>
