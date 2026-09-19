<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo_3ecfhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jo_3ecfhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:shopping-basket" {...props}></Icon>
