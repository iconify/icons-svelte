<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1t2gqb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e1t2gqb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-info-filled" {...props}></Icon>
