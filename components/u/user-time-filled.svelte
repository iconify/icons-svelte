<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg3nfg2gw.css';
import '../../css/z/zhypwob1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg3nfg2gw"/><path class="zhypwob1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-time-filled" {...props}></Icon>
