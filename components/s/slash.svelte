<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k33nyj33x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k33nyj33x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:slash" {...props}></Icon>
