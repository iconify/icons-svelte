<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc_saacsa.css';
import '../../css/k/kaqsw12py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kc_saacsa"/><path class="kaqsw12py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:statamic-dark" {...props}></Icon>
