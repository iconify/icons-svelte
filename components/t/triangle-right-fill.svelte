<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqjb9ibjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aqjb9ibjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:triangle-right-fill" {...props}></Icon>
