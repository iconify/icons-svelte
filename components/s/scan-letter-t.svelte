<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx3vb3kpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx3vb3kpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:scan-letter-t" {...props}></Icon>
