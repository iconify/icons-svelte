<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvw8lnbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nvw8lnbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:syringe" {...props}></Icon>
