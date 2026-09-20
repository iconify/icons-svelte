<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt0lgbd7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="qt0lgbd7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:snowmobile" {...props}></Icon>
