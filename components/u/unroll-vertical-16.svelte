<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzt4jjxuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mzt4jjxuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:unroll-vertical-16" {...props}></Icon>
