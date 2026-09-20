<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0wc3ts_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0wc3ts_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:song-recommendation-solid" {...props}></Icon>
