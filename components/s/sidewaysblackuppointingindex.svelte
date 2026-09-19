<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krdoyobux.css';
import '../../css/g/glhekuvna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="krdoyobux"/><path class="glhekuvna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sidewaysblackuppointingindex" {...props}></Icon>
