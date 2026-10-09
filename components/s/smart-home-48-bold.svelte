<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfpjugbvy.css';
import '../../css/b/blnw30haf.css';
import '../../css/f/fox5ysyus.css';
import '../../css/k/kurs2nb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="blnw30haf"/><path class="fox5ysyus"/><path class="kurs2nb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-home-48-bold" {...props}></Icon>
