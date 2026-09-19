<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-0k5mg3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u-0k5mg3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:world" {...props}></Icon>
