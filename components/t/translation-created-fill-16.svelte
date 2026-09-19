<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cut4v5iaq.css';
import '../../css/l/l4i1co0oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cut4v5iaq"/><path class="l4i1co0oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-created-fill-16" {...props}></Icon>
