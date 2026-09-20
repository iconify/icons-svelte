<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q07717bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q07717bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tugtainer-dark" {...props}></Icon>
