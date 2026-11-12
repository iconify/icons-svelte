<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2b4j_7ld.css';
import '../../css/b/bd6wcc_tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z2b4j_7ld"/><path class="bd6wcc_tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:virtualbox-light" {...props}></Icon>
