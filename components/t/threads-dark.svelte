<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gra6c-g-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gra6c-g-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:threads-dark" {...props}></Icon>
