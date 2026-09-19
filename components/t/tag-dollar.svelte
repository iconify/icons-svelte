<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d62mt21tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d62mt21tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:tag-dollar" {...props}></Icon>
