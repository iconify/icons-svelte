<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4187fbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4187fbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-voice-round" {...props}></Icon>
