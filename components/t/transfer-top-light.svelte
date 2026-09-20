<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjw90xqmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjw90xqmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-top-light" {...props}></Icon>
