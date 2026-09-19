<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaw9v0bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qaw9v0bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:share-outline" {...props}></Icon>
