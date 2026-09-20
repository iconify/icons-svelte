<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iycln-b8i.css';
import '../../css/g/g4i_lk0zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="iycln-b8i"/><path class="g4i_lk0zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yamlresume" {...props}></Icon>
