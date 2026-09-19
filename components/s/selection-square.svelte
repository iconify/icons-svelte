<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw8hk2oxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cw8hk2oxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:selection-square" {...props}></Icon>
