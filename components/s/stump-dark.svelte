<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coh2acbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="coh2acbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stump-dark" {...props}></Icon>
