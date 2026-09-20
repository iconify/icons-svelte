<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on5wcqudm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="on5wcqudm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wikipedia-dark" {...props}></Icon>
