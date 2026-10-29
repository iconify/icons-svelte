<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/djiqt-b-p.css';
import '../../css/k/kv-kaou7x.css';
import '../../css/p/prty8wg5d.css';
import '../../css/e/emha3wbqe.css';
import '../../css/p/p65k-7b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="djiqt-b-p wm-k"/><path class="kv-kaou7x wm-s"/><path class="prty8wg5d wm-shadow"/><path class="emha3wbqe wm-k"/><path class="p65k-7b9s wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-x-engrave" {...props}></Icon>
