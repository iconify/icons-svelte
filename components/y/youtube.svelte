<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxuzul_hm.css';
import '../../css/m/mrk6j-xvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxuzul_hm"/><path class="mrk6j-xvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtube" {...props}></Icon>
