<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h08hw7r7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h08hw7r7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:square" {...props}></Icon>
