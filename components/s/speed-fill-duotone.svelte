<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1oekvo1u.css';
import '../../css/y/y54-3102d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1oekvo1u"/><path clip-rule="evenodd" class="y54-3102d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:speed-fill-duotone" {...props}></Icon>
