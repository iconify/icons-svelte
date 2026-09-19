<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrrg9d2my.css';
import '../../css/y/yxxk2yx8a.css';
import '../../css/l/lb6m3_zjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nrrg9d2my"/><path class="yxxk2yx8a"/><path class="lb6m3_zjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:tags" {...props}></Icon>
