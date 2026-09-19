<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g22774ouw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g22774ouw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:toggle-on-solid" {...props}></Icon>
