<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcri59tzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bcri59tzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:share-outline" {...props}></Icon>
