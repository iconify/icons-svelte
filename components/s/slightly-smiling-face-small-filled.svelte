<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chmzr6tus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="chmzr6tus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:slightly-smiling-face-small-filled" {...props}></Icon>
