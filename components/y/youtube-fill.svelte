<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifilklg3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifilklg3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:youtube-fill" {...props}></Icon>
