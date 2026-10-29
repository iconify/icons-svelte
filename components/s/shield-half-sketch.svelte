<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ao44rhn1j.css';
import '../../css/b/bphei3uci.css';
import '../../css/h/hak54kboe.css';
import '../../css/a/akoy7wbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ao44rhn1j"/><path class="bphei3uci wm-k"/><path class="hak54kboe wm-k"/><path class="akoy7wbkr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-half-sketch" {...props}></Icon>
