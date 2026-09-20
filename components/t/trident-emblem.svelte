<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqqcd7bya.css';
import '../../css/g/ghnrm6ksq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hqqcd7bya"/><path class="ghnrm6ksq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:trident-emblem" {...props}></Icon>
