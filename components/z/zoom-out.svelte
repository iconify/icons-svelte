<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2_k3ejup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="h2_k3ejup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:zoom-out" {...props}></Icon>
