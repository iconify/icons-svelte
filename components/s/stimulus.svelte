<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6hna0bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b6hna0bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stimulus" {...props}></Icon>
