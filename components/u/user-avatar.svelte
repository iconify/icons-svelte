<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt-zv9ths.css';
import '../../css/u/uzucf_p2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pt-zv9ths"/><path class="uzucf_p2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-avatar" {...props}></Icon>
