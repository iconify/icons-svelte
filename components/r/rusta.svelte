<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltgkmpbdc.css';
import '../../css/f/flakb15jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ltgkmpbdc"/><path class="flakb15jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rusta" {...props}></Icon>
