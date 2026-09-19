<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iby16ob0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="iby16ob0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni597d-box-filled" {...props}></Icon>
