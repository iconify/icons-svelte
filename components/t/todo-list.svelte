<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wktbs6b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wktbs6b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:todo-list" {...props}></Icon>
