<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn1n32bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn1n32bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-bag-3-fill" {...props}></Icon>
