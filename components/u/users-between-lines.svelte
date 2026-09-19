<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trcf_86qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="trcf_86qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:users-between-lines" {...props}></Icon>
