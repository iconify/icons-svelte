<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac0esgq2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ac0esgq2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:volume-off" {...props}></Icon>
