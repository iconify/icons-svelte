<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqs8f3gob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eqs8f3gob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:usb-memory-stick" {...props}></Icon>
