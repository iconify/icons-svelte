<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywyq4xb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ywyq4xb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:thumbs-down" {...props}></Icon>
