<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndjxw_bam.css';
import '../../css/p/p2vf_po5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndjxw_bam"/><path class="p2vf_po5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:space" {...props}></Icon>
