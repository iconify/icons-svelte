<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3rkdqnsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3rkdqnsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ticket-sale-bold" {...props}></Icon>
