<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kauthwa8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kauthwa8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storygraph-dark" {...props}></Icon>
