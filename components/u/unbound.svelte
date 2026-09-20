<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqw05nt-o.css';
import '../../css/c/cqbk9ybmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqw05nt-o"/><path class="cqbk9ybmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unbound" {...props}></Icon>
