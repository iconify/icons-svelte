<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqbzs7b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hqbzs7b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:subtitles-sharp-fill" {...props}></Icon>
