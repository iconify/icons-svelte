<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et3kqvbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="et3kqvbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-basket-2-solid" {...props}></Icon>
