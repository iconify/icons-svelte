<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvi0-fb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvi0-fb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:user-voice-sharp" {...props}></Icon>
