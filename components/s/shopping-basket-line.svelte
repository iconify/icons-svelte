<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8qmhyqul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8qmhyqul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-basket-line" {...props}></Icon>
