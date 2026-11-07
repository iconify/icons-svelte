<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpywgebrg.css';
import '../../css/v/v2zklq74z.css';
import '../../css/c/cg22ifrfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpywgebrg"/><path class="v2zklq74z"/><path class="cg22ifrfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-2-bold-duotone" {...props}></Icon>
