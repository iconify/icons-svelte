<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5rhzabru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g5rhzabru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:television-filled" {...props}></Icon>
