<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfx7l-bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfx7l-bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:stop-circle" {...props}></Icon>
