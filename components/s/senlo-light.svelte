<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prmy9wtgl.css';
import '../../css/t/t8vej38_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="prmy9wtgl"/><path class="t8vej38_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:senlo-light" {...props}></Icon>
