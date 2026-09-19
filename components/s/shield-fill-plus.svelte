<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw1gbqudo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yw1gbqudo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shield-fill-plus" {...props}></Icon>
