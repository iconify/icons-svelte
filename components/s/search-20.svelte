<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsx9bkbtz.css';
import '../../css/b/bqcr30b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jsx9bkbtz"/><path class="bqcr30b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:search-20" {...props}></Icon>
