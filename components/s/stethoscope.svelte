<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktd933pvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ktd933pvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:stethoscope" {...props}></Icon>
