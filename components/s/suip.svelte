<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh7ww0b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh7ww0b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:suip" {...props}></Icon>
