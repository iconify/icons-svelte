<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bna-rjbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bna-rjbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:youtube-fill-16" {...props}></Icon>
