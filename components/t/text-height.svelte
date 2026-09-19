<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjn--bcyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jjn--bcyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:text-height" {...props}></Icon>
