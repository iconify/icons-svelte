<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8w4fvb8t.css';
import '../../css/i/i2a_ir9nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8w4fvb8t"/><path class="i2a_ir9nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yundera-light" {...props}></Icon>
