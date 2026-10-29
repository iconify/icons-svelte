<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp0rrubaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp0rrubaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skull-solid" {...props}></Icon>
