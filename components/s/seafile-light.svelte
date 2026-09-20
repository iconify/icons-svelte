<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aao1s0bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aao1s0bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seafile-light" {...props}></Icon>
