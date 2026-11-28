<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/df_igmx4m.css';
import '../../css/d/d-f_kel6u.css';
import '../../css/x/xxgdw-btn.css';
import '../../css/q/qy38zdwvn.css';
import '../../css/l/lw51043_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="df_igmx4m"/><path class="d-f_kel6u"/><path class="xxgdw-btn"/><path class="qy38zdwvn"/><path class="lw51043_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:waveform-low-duo" {...props}></Icon>
