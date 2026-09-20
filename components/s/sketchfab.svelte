<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h87x-4gom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h87x-4gom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sketchfab" {...props}></Icon>
