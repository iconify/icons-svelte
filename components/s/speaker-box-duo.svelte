<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqnzn2bgc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/thjkpabpk.css';
import '../../css/e/e5wrxmbgb.css';
import '../../css/g/ghjgxjbgi.css';
import '../../css/q/qm72ocbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqnzn2bgc secondary"/><g class="dt0cm9dhy primary"><path class="thjkpabpk"/><path class="e5wrxmbgb"/><path class="ghjgxjbgi"/><path class="qm72ocbza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:speaker-box-duo" {...props}></Icon>
