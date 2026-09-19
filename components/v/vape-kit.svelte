<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv42zablp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv42zablp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:vape-kit" {...props}></Icon>
