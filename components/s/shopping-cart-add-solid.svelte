<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6u38qb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6u38qb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shopping-cart-add-solid" {...props}></Icon>
