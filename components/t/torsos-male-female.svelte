<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofrrycbzm.css';
import '../../css/a/amz2rhbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ofrrycbzm"/><path class="amz2rhbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:torsos-male-female" {...props}></Icon>
