<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkveu1byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkveu1byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:v2raya-light" {...props}></Icon>
