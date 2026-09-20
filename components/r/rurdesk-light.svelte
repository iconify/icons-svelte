<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj9owmbzf.css';
import '../../css/a/a-4ue5bby.css';
import '../../css/u/u0kmufbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rj9owmbzf"/><path class="a-4ue5bby"/><circle class="u0kmufbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rurdesk-light" {...props}></Icon>
