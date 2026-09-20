<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go_6yoayx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go_6yoayx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:scissors-2" {...props}></Icon>
