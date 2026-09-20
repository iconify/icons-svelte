<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahfmtbc0f.css';
import '../../css/l/lf_du3q8d.css';
import '../../css/p/pgcktybjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahfmtbc0f"/><path class="lf_du3q8d"/><path class="pgcktybjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:web-section-alt" {...props}></Icon>
