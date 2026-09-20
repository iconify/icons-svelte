<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgbqb_cnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgbqb_cnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:watchyourports-dark" {...props}></Icon>
