<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8l0oobdd.css';
import '../../css/w/wg3u04byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a8l0oobdd"/><path class="wg3u04byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:shirt" {...props}></Icon>
