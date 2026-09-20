<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juh0qibpl.css';
import '../../css/q/qwbenrq8i.css';
import '../../css/w/wnm3xrb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="juh0qibpl"/><path class="qwbenrq8i"/><path class="wnm3xrb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:suggested-investigations" {...props}></Icon>
