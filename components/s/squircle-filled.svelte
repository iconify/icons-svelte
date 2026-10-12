<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnnbb5bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnnbb5bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:squircle-filled" {...props}></Icon>
