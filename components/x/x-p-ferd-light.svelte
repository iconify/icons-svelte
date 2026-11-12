<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdhn607fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tdhn607fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:x-p-ferd-light" {...props}></Icon>
