<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9o-8lbqq.css';
import '../../css/f/f9lebcb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9o-8lbqq"/><path clip-rule="evenodd" class="f9lebcb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:walking-bold" {...props}></Icon>
