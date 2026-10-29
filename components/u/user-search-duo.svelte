<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a_0c-vozs.css';
import '../../css/d/dgek29_2e.css';
import '../../css/t/t8eys6bao.css';
import '../../css/l/ljeitrr-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a_0c-vozs"/><path class="dgek29_2e wm-s"/><path class="t8eys6bao wm-s"/><path class="ljeitrr-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-search-duo" {...props}></Icon>
