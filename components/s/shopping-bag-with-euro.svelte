<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb61gly2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lb61gly2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-euro" {...props}></Icon>
