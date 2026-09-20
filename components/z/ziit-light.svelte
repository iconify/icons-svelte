<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clnygjb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="clnygjb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ziit-light" {...props}></Icon>
