<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6i609scc.css';
import '../../css/c/cnc48xb-n.css';
import '../../css/r/rtbltcbsy.css';
import '../../css/a/au6cvt0tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6i609scc"/><path class="cnc48xb-n"/><path class="rtbltcbsy"/><path class="au6cvt0tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:swise" {...props}></Icon>
