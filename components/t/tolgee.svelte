<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhj79ub0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhj79ub0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tolgee" {...props}></Icon>
