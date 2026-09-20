<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iclr56bfn.css';
import '../../css/w/wdgf1rbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iclr56bfn"/><path class="wdgf1rbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:stop-24" {...props}></Icon>
