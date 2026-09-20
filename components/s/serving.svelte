<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9q-2bb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l9q-2bb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:serving" {...props}></Icon>
