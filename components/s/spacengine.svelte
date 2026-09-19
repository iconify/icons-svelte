<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz9twfbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":474,"height":512};
const content = `<path class="wz9twfbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:spacengine" {...props}></Icon>
