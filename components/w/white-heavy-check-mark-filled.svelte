<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji29wxbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ji29wxbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-heavy-check-mark-filled" {...props}></Icon>
