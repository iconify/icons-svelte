<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xghsn32in.css';
import '../../css/h/hjo06mb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xghsn32in"/><path class="hjo06mb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tasmocompiler" {...props}></Icon>
