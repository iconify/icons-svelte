<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hutzjvbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hutzjvbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:triangle-half-filled" {...props}></Icon>
