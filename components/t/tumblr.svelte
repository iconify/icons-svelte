<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp6zbpa9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qp6zbpa9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tumblr" {...props}></Icon>
