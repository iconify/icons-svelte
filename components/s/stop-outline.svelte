<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b93j9cbjr.css';
import '../../css/d/dqndudb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b93j9cbjr"/><path class="dqndudb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stop-outline" {...props}></Icon>
