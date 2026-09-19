<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e12eedbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e12eedbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shopping-cart" {...props}></Icon>
