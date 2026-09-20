<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enl081bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="enl081bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:video-camera" {...props}></Icon>
