<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlgy4ybgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlgy4ybgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-basket-minus-filled" {...props}></Icon>
