<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/i769l5gsx.css';
import '../../css/c/c3b4mlqos.css';
import '../../css/g/gyv3og-gm.css';
import '../../css/e/e1ou-eb-u.css';
import '../../css/q/qru0v3g-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i769l5gsx"/><path class="c3b4mlqos"/><path class="gyv3og-gm"/><path class="e1ou-eb-u"/><path class="qru0v3g-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet-minus3" {...props}></Icon>
