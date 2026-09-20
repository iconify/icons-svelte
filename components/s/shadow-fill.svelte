<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvf2m-bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvf2m-bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shadow-fill" {...props}></Icon>
