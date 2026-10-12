<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cp8ajbcrx.css';
import '../../css/z/zan42xzig.css';
import '../../css/h/h67byabgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cp8ajbcrx"/><path class="zan42xzig"/><path class="h67byabgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ticket-slash-duotone" {...props}></Icon>
