<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5hki7bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c5hki7bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-basket-plus" {...props}></Icon>
