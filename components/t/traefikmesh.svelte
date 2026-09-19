<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3zpp1qvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s3zpp1qvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:traefikmesh" {...props}></Icon>
