<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i133w3y_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i133w3y_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ruler" {...props}></Icon>
