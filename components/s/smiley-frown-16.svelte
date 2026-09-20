<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1k5nzfab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n1k5nzfab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:smiley-frown-16" {...props}></Icon>
