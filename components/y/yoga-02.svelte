<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e5ch1xbsf.css';
import '../../css/x/xwroc2b7n.css';
import '../../css/n/nw4278f5v.css';
import '../../css/j/ju4c6cbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e5ch1xbsf"/><path class="xwroc2b7n"/><path class="nw4278f5v"/><path class="ju4c6cbsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:yoga-02" {...props}></Icon>
