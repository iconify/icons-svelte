<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/eif_5fngc.css';
import '../../css/y/yw2fz4bys.css';
import '../../css/o/obupwye0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="eif_5fngc"/><path class="yw2fz4bys"/><path class="obupwye0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:server" {...props}></Icon>
