<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf6ap-4vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jf6ap-4vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-replace" {...props}></Icon>
