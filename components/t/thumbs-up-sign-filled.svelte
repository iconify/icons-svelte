<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9zwtnb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g9zwtnb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:thumbs-up-sign-filled" {...props}></Icon>
