<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr0d_ccqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fr0d_ccqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-rupee" {...props}></Icon>
