<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w09nt7o0v.css';
import '../../css/h/hkt82pb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w09nt7o0v"/><path class="hkt82pb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:soup-filled" {...props}></Icon>
