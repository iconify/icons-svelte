<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj_v8nkfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj_v8nkfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zodiac-aquarius" {...props}></Icon>
