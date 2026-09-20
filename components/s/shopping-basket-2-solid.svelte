<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7ovob3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy7ovob3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shopping-basket-2-solid" {...props}></Icon>
