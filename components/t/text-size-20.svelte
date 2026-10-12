<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byu4-dbwe.css';
import '../../css/c/cffi7tb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="byu4-dbwe"/><path class="cffi7tb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-size-20" {...props}></Icon>
