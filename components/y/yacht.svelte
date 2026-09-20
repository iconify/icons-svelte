<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcwmn2dil.css';
import '../../css/r/rrczhp0ig.css';
import '../../css/b/b3q-odbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hcwmn2dil"/><path class="rrczhp0ig"/><path class="b3q-odbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yacht" {...props}></Icon>
