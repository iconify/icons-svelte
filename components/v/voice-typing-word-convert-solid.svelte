<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4nw3wu7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4nw3wu7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:voice-typing-word-convert-solid" {...props}></Icon>
