<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhmd9mu1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bhmd9mu1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:t-shirt" {...props}></Icon>
