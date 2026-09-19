<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5ic4hirb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c5ic4hirb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:x-octagon-fill" {...props}></Icon>
