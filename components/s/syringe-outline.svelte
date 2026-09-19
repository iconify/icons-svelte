<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5lolebbd.css';
import '../../css/x/xtcmkpb9n.css';
import '../../css/r/rzr-rcx2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5lolebbd"/><path clip-rule="evenodd" class="xtcmkpb9n"/><path clip-rule="evenodd" class="rzr-rcx2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:syringe-outline" {...props}></Icon>
