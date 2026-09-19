<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb-q8jbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb-q8jbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:undershirt-filled" {...props}></Icon>
