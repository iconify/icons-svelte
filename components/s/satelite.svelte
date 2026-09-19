<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7t30-klj.css';
import '../../css/n/nbg7fqb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s7t30-klj"/><path class="nbg7fqb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:satelite" {...props}></Icon>
