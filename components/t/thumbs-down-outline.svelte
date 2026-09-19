<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfv8uccdl.css';
import '../../css/g/gr-hcbcva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfv8uccdl"/><path class="gr-hcbcva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:thumbs-down-outline" {...props}></Icon>
