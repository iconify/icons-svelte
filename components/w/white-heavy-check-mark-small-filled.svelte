<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r60zgo13b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r60zgo13b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-heavy-check-mark-small-filled" {...props}></Icon>
