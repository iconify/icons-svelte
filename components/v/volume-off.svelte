<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/dc8ea8trm.css';
import '../../css/h/hk62-obry.css';
import '../../css/h/hhwgsyjct.css';
import '../../css/j/ja3fu9-gv.css';
import '../../css/w/wa9b2vb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="dc8ea8trm wm-shadow"/><path class="hk62-obry wm-shadow"/><path class="hhwgsyjct"/><path class="ja3fu9-gv"/><path class="wa9b2vb-y wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:volume-off" {...props}></Icon>
