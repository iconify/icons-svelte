<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvmp5sbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvmp5sbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:song-recommendation-remix" {...props}></Icon>
