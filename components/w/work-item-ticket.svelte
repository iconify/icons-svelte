<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh-9m4blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xh-9m4blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-ticket" {...props}></Icon>
