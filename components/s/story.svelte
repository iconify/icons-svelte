<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1e1ldbxe.css';
import '../../css/b/beggmnimb.css';
import '../../css/p/psrn3dbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1e1ldbxe"/><path class="beggmnimb"/><path class="psrn3dbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:story" {...props}></Icon>
