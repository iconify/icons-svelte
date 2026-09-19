<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp7bhvbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kp7bhvbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:violin" {...props}></Icon>
