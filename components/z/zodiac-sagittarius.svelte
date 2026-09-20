<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6wk7ac3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6wk7ac3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zodiac-sagittarius" {...props}></Icon>
