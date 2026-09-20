<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5t37qwas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5t37qwas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teamviewer" {...props}></Icon>
