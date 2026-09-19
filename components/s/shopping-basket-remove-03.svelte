<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9nlooiud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9nlooiud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shopping-basket-remove-03" {...props}></Icon>
