<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh9114-ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kh9114-ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:voice-mail-remix" {...props}></Icon>
