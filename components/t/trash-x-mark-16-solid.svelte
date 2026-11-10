<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n93l26b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n93l26b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:trash-x-mark-16-solid" {...props}></Icon>
