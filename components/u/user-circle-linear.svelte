<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lcfnqzkei.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/g/g2kki9-kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lcfnqzkei"/><circle class="shu3xdl9q"/><path class="g2kki9-kx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-circle-linear" {...props}></Icon>
