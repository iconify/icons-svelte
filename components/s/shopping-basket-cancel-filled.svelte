<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sowc0zb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sowc0zb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-basket-cancel-filled" {...props}></Icon>
