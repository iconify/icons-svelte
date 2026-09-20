<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfa0v7h4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfa0v7h4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:slash-light" {...props}></Icon>
