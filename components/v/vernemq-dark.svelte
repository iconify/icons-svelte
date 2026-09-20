<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0d80ubpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0d80ubpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vernemq-dark" {...props}></Icon>
