<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq-hce4iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq-hce4iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-cut" {...props}></Icon>
