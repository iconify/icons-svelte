<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rarc7rbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rarc7rbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shopping-bag-check-solid" {...props}></Icon>
