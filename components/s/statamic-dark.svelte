<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw28vh9ds.css';
import '../../css/k/kaqsw12py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cw28vh9ds"/><path class="kaqsw12py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:statamic-dark" {...props}></Icon>
