<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beko8jbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="beko8jbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:triangle-thunderbolt" {...props}></Icon>
