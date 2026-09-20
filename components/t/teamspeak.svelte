<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x70cer9yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x70cer9yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:teamspeak" {...props}></Icon>
