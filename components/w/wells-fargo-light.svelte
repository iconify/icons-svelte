<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8yf87b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g8yf87b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wells-fargo-light" {...props}></Icon>
