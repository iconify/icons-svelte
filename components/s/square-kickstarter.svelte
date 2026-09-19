<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um4t85bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="um4t85bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-kickstarter" {...props}></Icon>
