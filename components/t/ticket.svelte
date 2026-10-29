<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi6qjf9kl.css';
import '../../css/r/r2g9dxfqu.css';
import '../../css/q/qkesd0bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi6qjf9kl"/><path class="r2g9dxfqu"/><path class="qkesd0bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:ticket" {...props}></Icon>
