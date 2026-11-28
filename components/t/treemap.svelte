<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mie31z6an.css';
import '../../css/x/xvr7q8bai.css';
import '../../css/x/xgkpmbcio.css';
import '../../css/b/bvqojtbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mie31z6an"/><path class="xvr7q8bai"/><path class="xgkpmbcio"/><path class="bvqojtbxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:treemap" {...props}></Icon>
