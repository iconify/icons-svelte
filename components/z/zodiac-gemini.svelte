<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iegig96lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iegig96lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zodiac-gemini" {...props}></Icon>
