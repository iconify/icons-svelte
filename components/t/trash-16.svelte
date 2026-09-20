<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le5en1tee.css';
import '../../css/e/el2152b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="le5en1tee"/><path clip-rule="evenodd" class="el2152b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:trash-16" {...props}></Icon>
