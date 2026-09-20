<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krwbbqbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krwbbqbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:spc" {...props}></Icon>
