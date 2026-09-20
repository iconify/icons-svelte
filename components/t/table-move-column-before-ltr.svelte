<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge46vpt7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ge46vpt7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-move-column-before-ltr" {...props}></Icon>
