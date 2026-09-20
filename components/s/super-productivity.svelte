<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8uw2mboa.css';
import '../../css/p/psr8s7bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="b8uw2mboa"/><path class="psr8s7bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:super-productivity" {...props}></Icon>
