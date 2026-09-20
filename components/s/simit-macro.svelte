<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpwa63brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fpwa63brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:simit-macro" {...props}></Icon>
