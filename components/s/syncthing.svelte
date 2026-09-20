<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-kdk-b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-kdk-b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:syncthing" {...props}></Icon>
