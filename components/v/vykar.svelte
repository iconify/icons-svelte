<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0rns4bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a0rns4bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vykar" {...props}></Icon>
