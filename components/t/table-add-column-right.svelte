<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilqa1rbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ilqa1rbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:table-add-column-right" {...props}></Icon>
