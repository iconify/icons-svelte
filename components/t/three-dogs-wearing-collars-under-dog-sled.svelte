<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmneqac1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pmneqac1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-dogs-wearing-collars-under-dog-sled" {...props}></Icon>
