<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stlwhqbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stlwhqbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:video-edit-slow-motion" {...props}></Icon>
