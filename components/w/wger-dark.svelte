<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm3j0cc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cm3j0cc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wger-dark" {...props}></Icon>
