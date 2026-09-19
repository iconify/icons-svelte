<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls_9ogb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ls_9ogb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:slack" {...props}></Icon>
