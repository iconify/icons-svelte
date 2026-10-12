<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgzjhytup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgzjhytup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sun-medium-filled" {...props}></Icon>
