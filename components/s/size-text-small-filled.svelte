<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctkupt07p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ctkupt07p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:size-text-small-filled" {...props}></Icon>
