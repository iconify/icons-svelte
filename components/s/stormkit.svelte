<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9jlqc4uo.css';
import '../../css/d/d5_4t-xws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q9jlqc4uo"/><path class="d5_4t-xws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stormkit" {...props}></Icon>
