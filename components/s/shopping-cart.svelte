<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_-sezehz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_-sezehz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shopping-cart" {...props}></Icon>
