<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cgi6aebyp.css';
import '../../css/j/jes-ovvpz.css';
import '../../css/e/ekmlpmtjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cgi6aebyp"/><path class="jes-ovvpz wm-a"/><path class="ekmlpmtjg wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:server-cog" {...props}></Icon>
