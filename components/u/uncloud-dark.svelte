<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of7jgjbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="of7jgjbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uncloud-dark" {...props}></Icon>
