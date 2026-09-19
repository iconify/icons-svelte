<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxa1bxbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="hxa1bxbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shapes-26" {...props}></Icon>
