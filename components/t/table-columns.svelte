<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqpsb7bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mqpsb7bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:table-columns" {...props}></Icon>
