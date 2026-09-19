<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs5ad85nx.css';
import '../../css/d/d6rwj94cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bs5ad85nx"/><path class="d6rwj94cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:search-outline" {...props}></Icon>
