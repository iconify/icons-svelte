<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh4rs-bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh4rs-bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:video-subtitles-remix" {...props}></Icon>
