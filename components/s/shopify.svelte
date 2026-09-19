<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekf-t3bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ekf-t3bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:shopify" {...props}></Icon>
