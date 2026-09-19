<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww0e8n4yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ww0e8n4yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:svelte" {...props}></Icon>
