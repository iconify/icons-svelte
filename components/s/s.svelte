<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3vembbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":326,"height":671};
const content = `<path class="t3vembbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:s" {...props}></Icon>
