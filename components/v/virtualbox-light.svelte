<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1hm4ub9h.css';
import '../../css/b/bd6wcc_tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1hm4ub9h"/><path class="bd6wcc_tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:virtualbox-light" {...props}></Icon>
