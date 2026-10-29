<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/je523pkwt.css';
import '../../css/s/s398h1por.css';
import '../../css/p/psnkz2bcb.css';
import '../../css/n/n_bx2obur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="je523pkwt wm-k"/><path class="s398h1por wm-shadow"/><path class="psnkz2bcb wm-k"/><path class="n_bx2obur wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:switch-camera-engrave" {...props}></Icon>
