<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qkm3xcbxk.css';
import '../../css/n/n4iu-sbqo.css';
import '../../css/x/xenr55hzn.css';
import '../../css/s/s_wp055nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qkm3xcbxk"/><path class="n4iu-sbqo"/><circle class="xenr55hzn"/><circle class="s_wp055nf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:van" {...props}></Icon>
