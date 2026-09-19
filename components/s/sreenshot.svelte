<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veqikhb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="veqikhb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sreenshot" {...props}></Icon>
