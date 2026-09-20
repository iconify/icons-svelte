<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x66e6iaec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x66e6iaec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:runtipi-dark" {...props}></Icon>
