<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbgd9ibyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jbgd9ibyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shopware-light" {...props}></Icon>
