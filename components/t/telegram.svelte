<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq1gg58db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="yq1gg58db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:telegram" {...props}></Icon>
