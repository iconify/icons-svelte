<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsi-fwbsz.css';
import '../../css/n/n90ye8oqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsi-fwbsz wm-k"/><path class="n90ye8oqo wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:superscript" {...props}></Icon>
