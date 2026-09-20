<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckex8b9yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckex8b9yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shopping-basket-sharp" {...props}></Icon>
