<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc1rkybia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc1rkybia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-bag-cancel-filled" {...props}></Icon>
