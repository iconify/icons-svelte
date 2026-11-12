<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfa4qjb2q.css';
import '../../css/p/psr8s7bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="kfa4qjb2q"/><path class="psr8s7bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:super-productivity" {...props}></Icon>
