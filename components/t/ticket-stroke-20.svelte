<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3jzqsvjd.css';
import '../../css/o/o1j_wmpcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f3jzqsvjd"/><path class="o1j_wmpcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:ticket-stroke-20" {...props}></Icon>
