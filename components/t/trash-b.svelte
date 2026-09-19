<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1x2-08ga.css';
import '../../css/z/zzq0s9bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1x2-08ga"/><path class="zzq0s9bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trash-b" {...props}></Icon>
