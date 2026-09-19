<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agfd4ibou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="agfd4ibou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:vimeo" {...props}></Icon>
