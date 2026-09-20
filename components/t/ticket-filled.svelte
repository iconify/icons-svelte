<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqqwndb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pqqwndb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ticket-filled" {...props}></Icon>
