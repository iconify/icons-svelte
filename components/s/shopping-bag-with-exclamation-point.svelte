<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng5pvcbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ng5pvcbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-exclamation-point" {...props}></Icon>
