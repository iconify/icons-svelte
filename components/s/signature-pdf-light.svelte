<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emtqbdbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="emtqbdbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:signature-pdf-light" {...props}></Icon>
