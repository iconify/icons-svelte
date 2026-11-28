<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1l_u5b8t.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pzxc_4bsf.css';
import '../../css/c/cehc4fp0p.css';
import '../../css/d/d0jwgjpuu.css';
import '../../css/k/kt5dpkb2a.css';
import '../../css/m/ma71cib5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1l_u5b8t secondary"/><g class="dt0cm9dhy primary"><path class="pzxc_4bsf"/><path class="cehc4fp0p"/><path class="d0jwgjpuu"/><path class="kt5dpkb2a"/><path class="ma71cib5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vector-corner-duo" {...props}></Icon>
