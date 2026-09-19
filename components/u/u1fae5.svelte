<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5xaqcc6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m5xaqcc6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:u1fae5" {...props}></Icon>
