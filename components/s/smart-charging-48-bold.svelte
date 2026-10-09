<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0-a1391i.css';
import '../../css/a/a8ib1rb2l.css';
import '../../css/h/h0q19snmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w0-a1391i"/><path class="a8ib1rb2l"/><path class="h0q19snmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-charging-48-bold" {...props}></Icon>
