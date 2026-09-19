<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb1zz1gdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb1zz1gdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:youtube-filled" {...props}></Icon>
