<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdbm3gb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mdbm3gb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-loading-solid" {...props}></Icon>
