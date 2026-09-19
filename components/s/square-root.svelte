<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caqrw6b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="caqrw6b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:square-root" {...props}></Icon>
