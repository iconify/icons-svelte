<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rd2hxhb-u.css';
import '../../css/x/xtsrmvj7o.css';
import '../../css/b/bopi9b9jn.css';
import '../../css/f/fxwnb7vgp.css';
import '../../css/p/p9vjoqtlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rd2hxhb-u"/><circle class="xtsrmvj7o"/><circle class="bopi9b9jn"/><circle class="fxwnb7vgp"/><circle class="p9vjoqtlo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:vector-square" {...props}></Icon>
