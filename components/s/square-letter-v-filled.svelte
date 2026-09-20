<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctwjt065s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctwjt065s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-v-filled" {...props}></Icon>
