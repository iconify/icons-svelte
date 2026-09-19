<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeqki-bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="eeqki-bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:smile" {...props}></Icon>
