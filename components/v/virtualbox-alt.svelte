<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnhb0ybms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pnhb0ybms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:virtualbox-alt" {...props}></Icon>
