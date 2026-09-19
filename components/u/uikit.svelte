<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb1vmp6po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bb1vmp6po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:uikit" {...props}></Icon>
