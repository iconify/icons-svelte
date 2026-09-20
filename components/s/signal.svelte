<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzf5gacfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzf5gacfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:signal" {...props}></Icon>
