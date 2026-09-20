<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn2qr4boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fn2qr4boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tune-adjust-volume-remix" {...props}></Icon>
