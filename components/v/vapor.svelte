<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exr2ebttr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exr2ebttr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vapor" {...props}></Icon>
