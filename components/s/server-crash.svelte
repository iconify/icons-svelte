<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/w-b568bty.css';
import '../../css/m/mw-8r82fo.css';
import '../../css/a/abgj0wbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-b568bty"/><path class="mw-8r82fo"/><path class="abgj0wbue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:server-crash" {...props}></Icon>
