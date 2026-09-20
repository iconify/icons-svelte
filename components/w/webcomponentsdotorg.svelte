<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suw6_ccmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suw6_ccmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:webcomponentsdotorg" {...props}></Icon>
