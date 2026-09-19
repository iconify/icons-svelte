<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1swvfb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1swvfb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-basket-check-filled" {...props}></Icon>
