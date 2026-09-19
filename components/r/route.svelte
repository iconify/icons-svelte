<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok--3pvjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ok--3pvjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:route" {...props}></Icon>
