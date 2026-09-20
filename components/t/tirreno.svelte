<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4gv-v-ly.css';
import '../../css/u/uwxio7x7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4gv-v-ly"/><path class="uwxio7x7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tirreno" {...props}></Icon>
