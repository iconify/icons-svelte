<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irb-tcb5g.css';
import '../../css/k/kt2e20byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23.3,"height":25.7};
const content = `<path class="irb-tcb5g"/><path class="kt2e20byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:unit" {...props}></Icon>
