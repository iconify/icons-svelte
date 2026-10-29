<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq5w33b7p.css';
import '../../css/c/cjpxibctb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq5w33b7p wm-k"/><path class="cjpxibctb wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:skip-forward" {...props}></Icon>
