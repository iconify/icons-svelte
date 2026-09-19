<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv1sajb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kv1sajb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:stackbit" {...props}></Icon>
