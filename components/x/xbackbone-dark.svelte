<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekct923ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ekct923ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xbackbone-dark" {...props}></Icon>
