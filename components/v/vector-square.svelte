<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya8ta1jqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ya8ta1jqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vector-square" {...props}></Icon>
