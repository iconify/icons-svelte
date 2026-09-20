<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yle_3hkkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yle_3hkkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xbox-game-pass-light" {...props}></Icon>
