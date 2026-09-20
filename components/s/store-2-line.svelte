<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhjnutkmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhjnutkmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:store-2-line" {...props}></Icon>
