<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6-c3x6kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d6-c3x6kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:user-gender-female" {...props}></Icon>
