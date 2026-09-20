<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7c3h9bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u7c3h9bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:safari-outline" {...props}></Icon>
