<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it8ye198a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it8ye198a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:whistle-filled" {...props}></Icon>
