<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs9a2ybxg.css';
import '../../css/w/wgs1lgb3u.css';
import '../../css/m/m15-ptwxd.css';
import '../../css/a/ab7x2lbyj.css';
import '../../css/q/qi68hf0dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xs9a2ybxg"/><path class="wgs1lgb3u"/><path class="m15-ptwxd"/><path class="ab7x2lbyj"/><path class="qi68hf0dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swarmpit" {...props}></Icon>
