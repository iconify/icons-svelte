<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/ta6211bvx.css';
import '../../css/m/m53qvnbuy.css';
import '../../css/u/u4et_3yps.css';
import '../../css/x/x5vqjc9kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ta6211bvx"/><path class="m53qvnbuy"/><path class="u4et_3yps"/><path class="x5vqjc9kw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stethoscope" {...props}></Icon>
