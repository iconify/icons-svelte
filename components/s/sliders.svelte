<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drg-ult2l.css';
import '../../css/o/od-bcwuhn.css';
import '../../css/z/z2qezj3es.css';
import '../../css/q/qeewa2xbq.css';
import '../../css/d/dekk8gbpu.css';
import '../../css/w/w5frn37fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drg-ult2l wm-shadow"/><path class="od-bcwuhn wm-k"/><path class="wm-a z2qezj3es"/><path class="qeewa2xbq wm-a"/><path class="dekk8gbpu wm-a"/><path class="w5frn37fo wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:sliders" {...props}></Icon>
