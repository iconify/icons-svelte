<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lurj54bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lurj54bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:steam-dark" {...props}></Icon>
