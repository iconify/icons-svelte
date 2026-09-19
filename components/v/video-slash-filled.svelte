<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulw0feb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulw0feb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:video-slash-filled" {...props}></Icon>
