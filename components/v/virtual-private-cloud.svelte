<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8a0o-eya.css';
import '../../css/b/bde2b1vcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y8a0o-eya"/><path class="bde2b1vcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:virtual-private-cloud" {...props}></Icon>
