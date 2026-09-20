<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/aqg2-5bbs.css';
import '../../css/k/kib7r1wvv.css';
import '../../css/k/kvsiuof9s.css';
import '../../css/v/vri-l7yab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="aqg2-5bbs"/><path class="kib7r1wvv"/><path class="kvsiuof9s"/><path class="vri-l7yab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:server-error-404-not-found" {...props}></Icon>
