<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr-36obqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr-36obqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scale-filled" {...props}></Icon>
