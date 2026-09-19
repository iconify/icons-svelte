<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yokzwwjel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yokzwwjel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:temperature-low" {...props}></Icon>
