<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukpjozb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukpjozb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tumblr-fill" {...props}></Icon>
