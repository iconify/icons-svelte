<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp18n-bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jp18n-bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-venus" {...props}></Icon>
