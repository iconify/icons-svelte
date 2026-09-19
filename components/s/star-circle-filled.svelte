<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb0yj6ylj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb0yj6ylj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:star-circle-filled" {...props}></Icon>
