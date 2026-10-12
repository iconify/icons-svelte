<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dste_4pjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dste_4pjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sun-moon-filled" {...props}></Icon>
