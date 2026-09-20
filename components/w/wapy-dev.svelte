<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af9rt6b7c.css';
import '../../css/h/heyvp3bvx.css';
import '../../css/q/qioeu_bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="af9rt6b7c"/><path class="heyvp3bvx"/><path class="qioeu_bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wapy-dev" {...props}></Icon>
