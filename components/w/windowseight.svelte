<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpf2y9b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tpf2y9b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:windowseight" {...props}></Icon>
