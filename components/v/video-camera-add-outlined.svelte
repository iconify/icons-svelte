<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4utkdd9g.css';
import '../../css/r/r9wf1hbpk.css';
import '../../css/s/sa3sebesr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x4utkdd9g"/><path class="r9wf1hbpk"/><path class="sa3sebesr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:video-camera-add-outlined" {...props}></Icon>
