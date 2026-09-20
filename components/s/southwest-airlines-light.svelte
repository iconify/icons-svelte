<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umyqa91-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="umyqa91-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:southwest-airlines-light" {...props}></Icon>
