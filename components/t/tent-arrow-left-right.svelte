<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s36fjhbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s36fjhbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tent-arrow-left-right" {...props}></Icon>
