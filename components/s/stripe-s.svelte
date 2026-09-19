<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alh_6ac7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="alh_6ac7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:stripe-s" {...props}></Icon>
