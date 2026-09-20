<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxht3kjug.css';
import '../../css/j/jm_1qebhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gxht3kjug"/><path class="jm_1qebhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zrok-light" {...props}></Icon>
