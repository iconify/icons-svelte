<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm3geac7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm3geac7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:select-all-solid" {...props}></Icon>
