<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu49r2jkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uu49r2jkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-basket-minus" {...props}></Icon>
