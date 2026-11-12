<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqrktx3bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gqrktx3bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:systemd-wordmark" {...props}></Icon>
