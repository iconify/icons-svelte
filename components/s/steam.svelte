<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-s9v8b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="k-s9v8b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:steam" {...props}></Icon>
