<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s115isbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s115isbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:select-all" {...props}></Icon>
