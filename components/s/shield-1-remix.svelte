<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtehi7nkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gtehi7nkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shield-1-remix" {...props}></Icon>
