<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsu3e4aql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qsu3e4aql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:share-alt-solid" {...props}></Icon>
