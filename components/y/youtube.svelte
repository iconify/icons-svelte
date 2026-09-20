<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akt15xbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akt15xbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:youtube" {...props}></Icon>
