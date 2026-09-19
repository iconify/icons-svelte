<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcardlb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bcardlb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:workspace-trusted" {...props}></Icon>
