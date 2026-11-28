<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb65p4bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb65p4bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-leo-solid" {...props}></Icon>
