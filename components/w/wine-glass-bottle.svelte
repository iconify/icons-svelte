<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwuge2bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwuge2bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:wine-glass-bottle" {...props}></Icon>
