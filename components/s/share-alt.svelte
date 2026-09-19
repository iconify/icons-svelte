<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz6jnetqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vz6jnetqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:share-alt" {...props}></Icon>
