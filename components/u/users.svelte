<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd9lj4vea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rd9lj4vea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:users" {...props}></Icon>
