<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s55_9jckw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s55_9jckw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-play-h" {...props}></Icon>
