<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prsaaacnj.css';
import '../../css/x/xvgir7w9l.css';
import '../../css/r/r84512iun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prsaaacnj wm-k"/><path class="wm-k xvgir7w9l"/><path class="r84512iun wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:scroll-text" {...props}></Icon>
