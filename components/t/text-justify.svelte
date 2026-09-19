<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmcspk2nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hmcspk2nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-justify" {...props}></Icon>
