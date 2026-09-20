<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdql8tbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hdql8tbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:writefreely-light" {...props}></Icon>
