<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asop52brs.css';
import '../../css/p/pio8nkbyn.css';
import '../../css/h/hiktgyb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="asop52brs"/><path class="pio8nkbyn"/><path class="hiktgyb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:steam-reformer-48" {...props}></Icon>
