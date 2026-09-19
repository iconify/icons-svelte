<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj0cu-bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="aj0cu-bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:three-button-mouse" {...props}></Icon>
