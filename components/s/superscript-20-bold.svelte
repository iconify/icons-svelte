<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4q8gybuy.css';
import '../../css/p/pl0eixign.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a4q8gybuy"/><path class="pl0eixign"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:superscript-20-bold" {...props}></Icon>
