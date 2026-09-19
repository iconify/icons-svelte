<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi_4xcbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi_4xcbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:saudi-quran-ch" {...props}></Icon>
