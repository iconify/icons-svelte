<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvz532lhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fvz532lhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trmnl-light" {...props}></Icon>
