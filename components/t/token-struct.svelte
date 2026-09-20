<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spfghmjsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spfghmjsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-struct" {...props}></Icon>
