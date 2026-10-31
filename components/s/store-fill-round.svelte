<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1mtn1e3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1mtn1e3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:store-fill-round" {...props}></Icon>
