<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qze8yex4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qze8yex4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:spacemacs" {...props}></Icon>
