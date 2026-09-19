<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h__prbc9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="h__prbc9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-badge-minus" {...props}></Icon>
