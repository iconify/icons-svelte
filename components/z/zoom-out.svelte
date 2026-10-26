<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsg68bc0n.css';
import '../../css/s/s5p35abnm.css';
import '../../css/l/lf5qjjiit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="qsg68bc0n"><path class="s5p35abnm"/><path class="lf5qjjiit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:zoom-out" {...props}></Icon>
