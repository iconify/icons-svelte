<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6k5hvufk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6k5hvufk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spotify-dark" {...props}></Icon>
