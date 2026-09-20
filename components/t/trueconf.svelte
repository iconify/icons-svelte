<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pojo69bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pojo69bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trueconf" {...props}></Icon>
