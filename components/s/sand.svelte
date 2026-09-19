<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x61cv7ysi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x61cv7ysi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sand" {...props}></Icon>
