<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/b/b4jtc2s1i.css';
import '../../css/u/u5hrd1bpr.css';
import '../../css/u/uqq7glb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><path class="b4jtc2s1i"/><path class="u5hrd1bpr"/><path class="uqq7glb-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:winking-face" {...props}></Icon>
