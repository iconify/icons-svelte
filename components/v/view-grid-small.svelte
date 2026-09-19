<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qafyagj9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qafyagj9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:view-grid-small" {...props}></Icon>
