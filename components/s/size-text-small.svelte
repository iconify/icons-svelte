<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m60n7yb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m60n7yb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:size-text-small" {...props}></Icon>
