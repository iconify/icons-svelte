<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mit5m27lp.css';
import '../../css/b/b5cbtex2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mit5m27lp"/><path class="b5cbtex2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:volume-off-outline" {...props}></Icon>
