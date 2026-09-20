<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voaf05beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="voaf05beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yunohost-dark" {...props}></Icon>
