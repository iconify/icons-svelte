<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0tx1tbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0tx1tbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-case-title" {...props}></Icon>
