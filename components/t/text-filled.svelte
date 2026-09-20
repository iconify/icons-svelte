<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-gsb4e3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o-gsb4e3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:text-filled" {...props}></Icon>
