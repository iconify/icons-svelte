<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huwzlxbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="huwzlxbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shield-fill-16" {...props}></Icon>
