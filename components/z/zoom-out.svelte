<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc0nou-7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uc0nou-7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:zoom-out" {...props}></Icon>
