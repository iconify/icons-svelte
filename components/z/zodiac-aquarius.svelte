<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azn6hubbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azn6hubbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:zodiac-aquarius" {...props}></Icon>
