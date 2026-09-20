<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8ziwgk5l.css';
import '../../css/e/er7ag9bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g8ziwgk5l"/><path class="er7ag9bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:workbrew" {...props}></Icon>
