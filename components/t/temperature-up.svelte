<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9bqp1kzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z9bqp1kzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:temperature-up" {...props}></Icon>
