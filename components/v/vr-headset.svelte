<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdf5t1bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kdf5t1bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:vr-headset" {...props}></Icon>
