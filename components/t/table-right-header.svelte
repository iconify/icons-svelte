<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvs2q08pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lvs2q08pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:table-right-header" {...props}></Icon>
