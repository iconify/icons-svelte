<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m1-vjp_xd.css';
import '../../css/z/zk92zjb_z.css';
import '../../css/d/dtrgj3edn.css';
import '../../css/u/usaw5gb_y.css';
import '../../css/c/chflpfbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m1-vjp_xd"/><path class="zk92zjb_z"/><path class="dtrgj3edn"/><path class="usaw5gb_y"/><path class="chflpfbrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ship" {...props}></Icon>
