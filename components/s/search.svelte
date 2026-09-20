<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrnk14kvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrnk14kvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search" {...props}></Icon>
