<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtd9lvb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jtd9lvb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:triangle-right" {...props}></Icon>
