<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dej0zfcri.css';
import '../../css/c/c3dz4vwtf.css';
import '../../css/i/ikx892b0n.css';
import '../../css/q/qrk7i-jmd.css';
import '../../css/e/e3mc55d5q.css';
import '../../css/o/o2280qffp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="dej0zfcri"/><circle class="c3dz4vwtf"/><circle class="ikx892b0n"/><path class="qrk7i-jmd"/><path class="e3mc55d5q"/><path class="o2280qffp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:sandbox" {...props}></Icon>
